<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m37772ano.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="m37772ano"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:strikethrough" {...props}></Icon>
