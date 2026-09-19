<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq3f4pbqc.css';
import '../../css/d/db3lwj71b.css';
import '../../css/y/yfqh42bcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="dq3f4pbqc"/><path class="db3lwj71b"/><path class="yfqh42bcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-amazon" {...props}></Icon>
