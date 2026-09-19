<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emgorab8j.css';
import '../../css/f/faez3bb4d.css';
import '../../css/p/pjip0acda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="emgorab8j"/><path class="faez3bb4d"/><path class="pjip0acda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-joomla" {...props}></Icon>
