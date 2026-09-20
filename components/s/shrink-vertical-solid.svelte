<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkxv-k3lx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkxv-k3lx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:shrink-vertical-solid" {...props}></Icon>
