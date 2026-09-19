<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sg4rycc9o.css';
import '../../css/q/qfttfgb8q.css';
import '../../css/d/djyvkb6-g.css';
import '../../css/f/frp7jbb5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="sg4rycc9o"/><path class="qfttfgb8q"/><path class="djyvkb6-g"/><path class="frp7jbb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:yii" {...props}></Icon>
