<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x57nb3bxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="x57nb3bxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:slightly-frowning-face-small" {...props}></Icon>
