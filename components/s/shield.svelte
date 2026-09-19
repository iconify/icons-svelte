<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwwv59bwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":520};
const content = `<path class="zwwv59bwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:shield" {...props}></Icon>
