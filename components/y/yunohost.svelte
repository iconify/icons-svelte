<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k88q8qb5o.css';
import '../../css/o/o250bhbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="k88q8qb5o"/><path class="o250bhbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:yunohost" {...props}></Icon>
