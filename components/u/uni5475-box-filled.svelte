<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpjd-ub0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="lpjd-ub0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:uni5475-box-filled" {...props}></Icon>
