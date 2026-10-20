<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxwb8tbxv.css';
import '../../css/d/dsco5xu2d.css';
import '../../css/e/e2j9qob0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pxwb8tbxv"/><path class="dsco5xu2d"/><path class="e2j9qob0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:test-tube-20" {...props}></Icon>
