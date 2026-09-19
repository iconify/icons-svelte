<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi7m7db4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="mi7m7db4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:top-hat" {...props}></Icon>
