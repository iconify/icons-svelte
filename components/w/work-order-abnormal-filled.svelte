<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4sc0yb1a.css';
import '../../css/q/qcjn5ubrr.css';
import '../../css/a/avgingbgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j4sc0yb1a"/><path class="qcjn5ubrr"/><path clip-rule="evenodd" class="avgingbgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:work-order-abnormal-filled" {...props}></Icon>
