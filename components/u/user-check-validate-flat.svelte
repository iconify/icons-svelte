<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/e/ej2rmtblx.css';
import '../../css/y/yr5bfmbag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ej2rmtblx"/><path class="yr5bfmbag"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:user-check-validate-flat" {...props}></Icon>
