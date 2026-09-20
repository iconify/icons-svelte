<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bg17mhb7c.css';
import '../../css/q/qyzx5zbrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":277};
const content = `<path class="bg17mhb7c"/><path class="qyzx5zbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vueuse" {...props}></Icon>
