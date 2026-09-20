<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfg596bgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pfg596bgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:sound-disable" {...props}></Icon>
