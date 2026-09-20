<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzolo-p4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="dzolo-p4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:security-checked" {...props}></Icon>
