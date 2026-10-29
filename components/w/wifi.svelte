<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvk2mbcwh.css';
import '../../css/e/egyf9jbvi.css';
import '../../css/g/gs45f_bze.css';
import '../../css/i/icly_ob1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jvk2mbcwh"/><path class="egyf9jbvi"/><path class="gs45f_bze"/><path class="icly_ob1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:wifi" {...props}></Icon>
