<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8ee6my5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y8ee6my5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:user-solid" {...props}></Icon>
