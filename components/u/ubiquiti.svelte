<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ga_huibig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ga_huibig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ubiquiti" {...props}></Icon>
