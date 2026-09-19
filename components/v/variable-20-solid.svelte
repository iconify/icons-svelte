<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylwo9q-ek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ylwo9q-ek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:variable-20-solid" {...props}></Icon>
