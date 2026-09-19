<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6re6y22q.css';
import '../../css/a/ak63jmbgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t6re6y22q"/><path class="ak63jmbgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:text-fill" {...props}></Icon>
