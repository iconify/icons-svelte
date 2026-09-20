<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_h18h.css';
import '../../css/t/t7y_kz.css';
import '../../css/f/fill-to-0.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-from-76.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x_h18h"/><path class="t7y_kz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:thumbs-down-twotone" {...props}></Icon>
