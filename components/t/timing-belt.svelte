<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3lbonbua.css';
import '../../css/b/bq5th6b_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="g3lbonbua"/><path class="bq5th6b_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:timing-belt" {...props}></Icon>
