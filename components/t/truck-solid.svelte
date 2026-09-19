<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6i949bga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k6i949bga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:truck-solid" {...props}></Icon>
