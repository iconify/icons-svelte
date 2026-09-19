<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imk4jgbjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="imk4jgbjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:ship" {...props}></Icon>
