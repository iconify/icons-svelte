<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pe5kl4b5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="pe5kl4b5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:uni6709-box" {...props}></Icon>
