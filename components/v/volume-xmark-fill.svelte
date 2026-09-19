<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1l4w0b0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="o1l4w0b0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:volume-xmark-fill" {...props}></Icon>
