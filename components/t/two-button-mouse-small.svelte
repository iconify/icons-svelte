<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jss17mrbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="jss17mrbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:two-button-mouse-small" {...props}></Icon>
