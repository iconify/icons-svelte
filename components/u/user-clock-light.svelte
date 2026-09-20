<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opg4asb0t.css';
import '../../css/l/lrijolbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="opg4asb0t"/><path class="lrijolbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:user-clock-light" {...props}></Icon>
