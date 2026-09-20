<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av-8j404k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<path class="av-8j404k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:trash-alt-f" {...props}></Icon>
