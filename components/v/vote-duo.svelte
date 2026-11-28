<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz--dybeb.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/dzkpl7bps.css';
import '../../css/p/p9wysibpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary zz--dybeb"/><g class="dt0cm9dhy primary"><path class="dzkpl7bps"/><path class="p9wysibpt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:vote-duo" {...props}></Icon>
