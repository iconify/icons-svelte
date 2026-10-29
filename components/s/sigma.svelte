<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlsti7bwm.css';
import '../../css/a/al-kcgb4q.css';
import '../../css/o/odm1sybxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wlsti7bwm wm-shadow"/><path class="al-kcgb4q wm-k"/><path class="odm1sybxw wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-pastel:sigma" {...props}></Icon>
