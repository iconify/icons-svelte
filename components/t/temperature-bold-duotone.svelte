<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6rfy3bcu.css';
import '../../css/a/a1b-yfidj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v6rfy3bcu"/><path class="a1b-yfidj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:temperature-bold-duotone" {...props}></Icon>
