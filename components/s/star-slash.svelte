<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm5trfjdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="qm5trfjdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:star-slash" {...props}></Icon>
