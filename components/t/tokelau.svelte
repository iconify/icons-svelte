<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymvjmwp_c.css';
import '../../css/l/lj8m_5b8h.css';
import '../../css/d/dealb4p_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="ymvjmwp_c"/><path class="lj8m_5b8h"/><path class="dealb4p_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:tokelau" {...props}></Icon>
