<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2-7v0z6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2-7v0z6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:square-solid" {...props}></Icon>
