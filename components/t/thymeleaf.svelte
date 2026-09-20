<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfbf8lbfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfbf8lbfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:thymeleaf" {...props}></Icon>
