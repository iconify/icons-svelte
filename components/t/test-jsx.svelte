<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nycdyjolw.css';
import '../../css/o/o7pmz67-b.css';
import '../../css/k/k8-ktvkft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nycdyjolw"/><circle class="o7pmz67-b"/><path class="k8-ktvkft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:test-jsx" {...props}></Icon>
