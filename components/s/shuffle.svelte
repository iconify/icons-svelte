<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4qu_kbxw.css';
import '../../css/j/jrj0xe63g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4qu_kbxw"/><path class="jrj0xe63g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:shuffle" {...props}></Icon>
