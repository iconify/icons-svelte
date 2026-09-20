<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw1iew.css';
import '../../css/o/oawv9t.css';
import '../../css/l/lotvgl.css';
import '../../css/d/d-viliiy.css';
import '../../css/s/so-from-20.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iw1iew oawv9t"/><path class="iw1iew lotvgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:upload-loop" {...props}></Icon>
