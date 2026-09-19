<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-ol9zsde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="c-ol9zsde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:unicode-small" {...props}></Icon>
