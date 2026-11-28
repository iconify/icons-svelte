<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/pd0bczbtd.css';
import '../../css/o/o-tkjmy1q.css';
import '../../css/b/bqs_bew3a.css';
import '../../css/q/qg0bq2b6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="pd0bczbtd"/><path class="o-tkjmy1q"/><path class="bqs_bew3a"/><path class="qg0bq2b6a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:wifi-duo" {...props}></Icon>
