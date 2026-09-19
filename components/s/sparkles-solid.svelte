<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekqxg0bdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ekqxg0bdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:sparkles-solid" {...props}></Icon>
