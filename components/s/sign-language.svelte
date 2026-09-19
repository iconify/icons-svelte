<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izlxtcbii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1792};
const content = `<path class="izlxtcbii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:sign-language" {...props}></Icon>
