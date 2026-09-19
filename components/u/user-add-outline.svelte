<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfs6ffbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfs6ffbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:user-add-outline" {...props}></Icon>
