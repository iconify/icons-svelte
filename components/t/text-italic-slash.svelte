<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/mx8-48i7a.css';
import '../../css/o/o1ic8yb3p.css';
import '../../css/j/jewv0ybko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mx8-48i7a"/><path class="o1ic8yb3p"/><path class="jewv0ybko"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:text-italic-slash" {...props}></Icon>
