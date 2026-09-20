<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/n/n2neiybmu.css';
import '../../css/h/he2cb6v8q.css';
import '../../css/q/qhj_kmfui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="n2neiybmu"/><path class="he2cb6v8q"/><path class="qhj_kmfui"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:shop-cart" {...props}></Icon>
