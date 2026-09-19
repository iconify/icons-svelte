<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avomhzplk.css';
import '../../css/x/xrwqa-u3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avomhzplk"/><path class="xrwqa-u3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:tennis-ball" {...props}></Icon>
