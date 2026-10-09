<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8zyk_juu.css';
import '../../css/b/bhtgracju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e8zyk_juu"/><path class="bhtgracju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:voltmeter-20" {...props}></Icon>
