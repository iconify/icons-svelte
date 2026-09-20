<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/ok4gpdcio.css';
import '../../css/h/hlpokcbfc.css';
import '../../css/w/w49sw5b-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="ok4gpdcio"/><circle class="hlpokcbfc"/><path class="w49sw5b-z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:user-cicrle" {...props}></Icon>
