<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sicut5b7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sicut5b7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:school-flag-alt-outline" {...props}></Icon>
