<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n5qlzhbvm.css';
import '../../css/i/i5_3pc0qy.css';
import '../../css/o/otk84v7nh.css';
import '../../css/t/t0oipbbbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="n5qlzhbvm"/><path class="i5_3pc0qy"/><path class="otk84v7nh"/><path class="t0oipbbbu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:watch-light" {...props}></Icon>
