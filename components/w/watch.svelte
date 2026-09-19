<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw2oufbxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="qw2oufbxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:watch" {...props}></Icon>
