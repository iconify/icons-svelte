<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9wh86bhu.css';
import '../../css/u/udfv0g6tu.css';
import '../../css/v/viull-tzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c9wh86bhu"/><path class="udfv0g6tu"/><path class="viull-tzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tea-cup-20-bold" {...props}></Icon>
