<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee_hsbbuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ee_hsbbuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:youtube-logo-remix" {...props}></Icon>
