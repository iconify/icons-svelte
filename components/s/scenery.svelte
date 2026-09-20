<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-jgm53ez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-jgm53ez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:scenery" {...props}></Icon>
