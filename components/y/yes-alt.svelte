<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlhlbkp3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zlhlbkp3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:yes-alt" {...props}></Icon>
