<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js_xa2bww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-5};
const content = `<path class="js_xa2bww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:youtube" {...props}></Icon>
