<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bryv9-bhw.css';
import '../../css/k/kb7fl3kua.css';
import '../../css/g/gd-r2cbpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bryv9-bhw"/><path class="kb7fl3kua"/><path class="gd-r2cbpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:worm-gear-20-bold" {...props}></Icon>
