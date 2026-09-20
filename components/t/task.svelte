<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erq7k8buo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="erq7k8buo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:task" {...props}></Icon>
