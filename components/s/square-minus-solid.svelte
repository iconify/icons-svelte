<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blalr_7lp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="blalr_7lp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:square-minus-solid" {...props}></Icon>
