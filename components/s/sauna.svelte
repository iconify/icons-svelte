<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya-my6ogs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ya-my6ogs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:sauna" {...props}></Icon>
