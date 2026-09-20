<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/a/a86yqyqva.css';
import '../../css/c/cbpc6zbgf.css';
import '../../css/w/w6crmdb4u.css';
import '../../css/m/m5eds2f1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a86yqyqva"/><circle class="cbpc6zbgf"/><path class="w6crmdb4u"/><circle class="m5eds2f1v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:skull-line" {...props}></Icon>
