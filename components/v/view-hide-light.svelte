<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/iwmf6ebpj.css';
import '../../css/f/f3xfz4hac.css';
import '../../css/o/ose_erblr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="iwmf6ebpj"/><path clip-rule="evenodd" class="f3xfz4hac"/><path class="ose_erblr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:view-hide-light" {...props}></Icon>
