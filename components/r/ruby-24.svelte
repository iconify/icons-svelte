<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyp2occig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oyp2occig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:ruby-24" {...props}></Icon>
