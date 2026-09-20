<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er8a8eblt.css';
import '../../css/c/c_exiz4cf.css';
import '../../css/d/dg3xy7bww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="er8a8eblt"/><path clip-rule="evenodd" class="c_exiz4cf"/><path class="dg3xy7bww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:slg" {...props}></Icon>
