<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plsztrl7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="plsztrl7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:vivint" {...props}></Icon>
