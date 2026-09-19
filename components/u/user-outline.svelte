<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbgz-if8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbgz-if8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:user-outline" {...props}></Icon>
