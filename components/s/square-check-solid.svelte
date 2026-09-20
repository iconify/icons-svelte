<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wone3cgvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wone3cgvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:square-check-solid" {...props}></Icon>
