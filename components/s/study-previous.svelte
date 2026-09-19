<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rojvpmb6a.css';
import '../../css/j/jy3p094dk.css';
import '../../css/j/j_7wf_9wv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rojvpmb6a"/><path class="jy3p094dk"/><path class="j_7wf_9wv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:study-previous" {...props}></Icon>
