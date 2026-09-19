<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh0qghayh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="lh0qghayh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:typo3" {...props}></Icon>
