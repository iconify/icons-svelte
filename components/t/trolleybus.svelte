<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au8nzfblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="au8nzfblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:trolleybus" {...props}></Icon>
