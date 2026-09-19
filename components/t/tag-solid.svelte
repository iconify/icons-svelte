<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdj-zf05d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdj-zf05d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:tag-solid" {...props}></Icon>
