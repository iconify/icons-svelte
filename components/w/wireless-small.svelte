<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svgy8st2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="svgy8st2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:wireless-small" {...props}></Icon>
