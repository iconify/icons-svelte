<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5syerbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="k5syerbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:stackofphotos" {...props}></Icon>
