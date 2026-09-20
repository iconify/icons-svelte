<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tksk2_b7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tksk2_b7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:stopstalk" {...props}></Icon>
