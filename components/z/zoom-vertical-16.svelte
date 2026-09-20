<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsqbu6bax.css';
import '../../css/b/b5tasac6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qsqbu6bax"/><path clip-rule="evenodd" class="b5tasac6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:zoom-vertical-16" {...props}></Icon>
