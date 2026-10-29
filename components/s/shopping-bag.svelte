<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsgqmskrc.css';
import '../../css/o/o0y5tdbqm.css';
import '../../css/s/sga_f_diy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fsgqmskrc wm-a"/><path class="o0y5tdbqm wm-k"/><path class="sga_f_diy wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:shopping-bag" {...props}></Icon>
