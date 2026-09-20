<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/p/phk9uibbc.css';
import '../../css/c/c5dd8mb9u.css';
import '../../css/h/h7sstobfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="phk9uibbc"/><path class="c5dd8mb9u"/><path class="h7sstobfk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:seat-vip" {...props}></Icon>
