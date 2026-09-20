<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zdw9dcb7o.css';
import '../../css/t/twdsh1b5k.css';
import '../../css/i/iz89bvbzi.css';
import '../../css/k/ki54dl-uc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="zdw9dcb7o"/><path clip-rule="evenodd" class="twdsh1b5k"/><path clip-rule="evenodd" class="iz89bvbzi"/><path clip-rule="evenodd" class="ki54dl-uc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="skill-icons:terraform-dark" {...props}></Icon>
