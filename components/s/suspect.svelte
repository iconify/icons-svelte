<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4-7eu8rv.css';
import '../../css/j/j8qutoidr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="v4-7eu8rv"/><path class="j8qutoidr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:suspect" {...props}></Icon>
