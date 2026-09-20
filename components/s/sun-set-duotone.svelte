<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i3qoh5kxx.css';
import '../../css/h/hdj4zg9nf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i3qoh5kxx"/><path class="hdj4zg9nf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:sun-set-duotone" {...props}></Icon>
