<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjec9ou5t.css';
import '../../css/z/z9fhmbbzq.css';
import '../../css/x/xom1eccnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pjec9ou5t"/><path class="z9fhmbbzq"/><path class="xom1eccnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:yes" {...props}></Icon>
