<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kehel7vqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="kehel7vqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:uni8349-circled-filled" {...props}></Icon>
