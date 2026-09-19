<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtqm8qbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="qtqm8qbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:textformat-abc" {...props}></Icon>
