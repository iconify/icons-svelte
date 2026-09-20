<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fru1dogiw.css';
import '../../css/l/ltqrw6w2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fru1dogiw"/><path class="ltqrw6w2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:sitar-16" {...props}></Icon>
