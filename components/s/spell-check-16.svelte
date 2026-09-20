<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsdaybuea.css';
import '../../css/t/tx00macjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hsdaybuea"/><path class="tx00macjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:spell-check-16" {...props}></Icon>
