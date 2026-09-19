<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g4d4f-b6h.css';
import '../../css/v/v1qda8bgr.css';
import '../../css/p/pujaovdwh.css';
import '../../css/o/ojrq0jbfh.css';
import '../../css/f/fkfneqw5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":49,"height":48};
const content = `<g class="ft5dv1b6b"><rect class="g4d4f-b6h"/><path class="v1qda8bgr"/><circle class="pujaovdwh"/><circle class="ojrq0jbfh"/><circle class="fkfneqw5u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:washing-machine" {...props}></Icon>
