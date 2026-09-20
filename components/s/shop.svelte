<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/i/ix6i1v8-a.css';
import '../../css/p/ptn4d776z.css';
import '../../css/w/w075vybfy.css';
import '../../css/f/fn13rwetu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ix6i1v8-a"/><path class="ptn4d776z"/><path class="w075vybfy"/><path class="fn13rwetu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:shop" {...props}></Icon>
