<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qng5m212p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="qng5m212p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:tuningfork" {...props}></Icon>
