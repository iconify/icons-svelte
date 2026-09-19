<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgzi0ccar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="bgzi0ccar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:speech-balloon" {...props}></Icon>
