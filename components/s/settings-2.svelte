<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/h/h8vg5hbbc.css';
import '../../css/c/ceitnjb9j.css';
import '../../css/b/bk5i81qzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h8vg5hbbc"/><circle class="ceitnjb9j"/><circle class="bk5i81qzz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:settings-2" {...props}></Icon>
