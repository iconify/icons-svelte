<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pep0p17_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pep0p17_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:text-align-justify-start" {...props}></Icon>
