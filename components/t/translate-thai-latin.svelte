<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgyph7b6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="zgyph7b6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:translate-thai-latin" {...props}></Icon>
