<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m18fk9bwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":528,"height":448};
const content = `<path class="m18fk9bwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:water-temperature-30" {...props}></Icon>
