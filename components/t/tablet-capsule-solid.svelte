<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz9n6kbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kz9n6kbsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:tablet-capsule-solid" {...props}></Icon>
