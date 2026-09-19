<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfbp08bap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="sfbp08bap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:uni8d5e-box-filled" {...props}></Icon>
