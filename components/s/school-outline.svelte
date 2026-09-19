<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gziqccc8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gziqccc8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:school-outline" {...props}></Icon>
