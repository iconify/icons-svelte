<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k5-vjlrin.css';
import '../../css/t/tkpd1op2o.css';
import '../../css/b/bd9gczbnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGg4efnesH"><path class="k5-vjlrin"/><path clip-rule="evenodd" class="tkpd1op2o"/></mask></defs><circle mask="url(#SVGg4efnesH)" class="bd9gczbnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:ruler-circle-filled" {...props}></Icon>
