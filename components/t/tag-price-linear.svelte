<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/jozserb6t.css';
import '../../css/z/zf6m_rg7v.css';
import '../../css/o/ozst3gb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jozserb6t"/><path class="zf6m_rg7v"/><circle transform="rotate(-45 8.607 8.88)" class="ozst3gb1r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:tag-price-linear" {...props}></Icon>
