<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9iuzurti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="g9iuzurti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:telegram-alt" {...props}></Icon>
