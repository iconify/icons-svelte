<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw2d8kh4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="qw2d8kh4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:shopping-trolley-small" {...props}></Icon>
