<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmf13t2li.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tmf13t2li"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:text-size-solid" {...props}></Icon>
