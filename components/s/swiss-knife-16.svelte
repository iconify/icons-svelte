<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h29-mkxmi.css';
import '../../css/d/d4ur63wtm.css';
import '../../css/i/ih216efdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h29-mkxmi"/><path clip-rule="evenodd" class="d4ur63wtm"/><path class="ih216efdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:swiss-knife-16" {...props}></Icon>
