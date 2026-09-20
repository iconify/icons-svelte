<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcdzevfcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kcdzevfcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:thumbs-down" {...props}></Icon>
