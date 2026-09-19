<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glkv8ob8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="glkv8ob8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:scalpel" {...props}></Icon>
