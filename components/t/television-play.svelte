<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/i/il0hwjnhw.css';
import '../../css/w/w-_7y_bds.css';
import '../../css/b/bcw8vgbgs.css';
import '../../css/k/kxrlahbnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="il0hwjnhw"/><path class="w-_7y_bds"/><path class="bcw8vgbgs"/><path class="kxrlahbnk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:television-play" {...props}></Icon>
