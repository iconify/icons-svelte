<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5xdmn.css';
import '../../css/o/of3gku.css';
import '../../css/o/oxx-om.css';
import '../../css/q/qaqxso.css';
import '../../css/b/botfzx.css';
import '../../css/g/gd_4-q.css';
import '../../css/s/so-from-22.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGcMlHtdME"><path class="c5xdmn of3gku"/><path class="c5xdmn oxx-om qaqxso"/></mask></defs><path mask="url(#SVGcMlHtdME)" class="botfzx"/><path class="c5xdmn gd_4-q qaqxso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:water-off" {...props}></Icon>
