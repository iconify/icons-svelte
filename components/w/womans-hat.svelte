<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4uihebjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="r4uihebjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:womans-hat" {...props}></Icon>
