<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/j/jn5ns-bvo.css';
import '../../css/c/c105892kk.css';
import '../../css/v/vbin-qbry.css';
import '../../css/t/t8s921bqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="jn5ns-bvo"/><path class="c105892kk"/><path class="vbin-qbry"/><path class="t8s921bqp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:vinyl-record-gramophone" {...props}></Icon>
